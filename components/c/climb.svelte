<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xriuw52tl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xriuw52tl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:climb" {...props}></Icon>
