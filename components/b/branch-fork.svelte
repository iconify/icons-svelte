<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uan6h8bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uan6h8bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:branch-fork" {...props}></Icon>
