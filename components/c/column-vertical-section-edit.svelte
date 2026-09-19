<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzjb8eqmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mzjb8eqmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:column-vertical-section-edit" {...props}></Icon>
