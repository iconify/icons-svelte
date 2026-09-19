<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0y2p2isn.css';
import '../../css/p/pr22v0bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0y2p2isn"/><path class="pr22v0bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:circle-chev-down" {...props}></Icon>
