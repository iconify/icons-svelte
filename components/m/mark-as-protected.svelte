<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1hr5fdkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="l1hr5fdkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:mark-as-protected" {...props}></Icon>
