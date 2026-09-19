<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybps4ubau.css';
import '../../css/s/sh39ly0gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybps4ubau"/><path class="sh39ly0gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-cricket-ball" {...props}></Icon>
