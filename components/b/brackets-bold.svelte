<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_z3u7nyx.css';
import '../../css/w/whtgogiyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_z3u7nyx"/><path class="whtgogiyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:brackets-bold" {...props}></Icon>
