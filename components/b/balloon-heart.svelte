<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm88y3bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm88y3bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:balloon-heart" {...props}></Icon>
