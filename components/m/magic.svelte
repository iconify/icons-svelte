<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_pc-t0wl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c_pc-t0wl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:magic" {...props}></Icon>
