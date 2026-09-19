<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5wi-ryfk.css';
import '../../css/d/dtfkzwyic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5wi-ryfk"/><path class="dtfkzwyic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-alarm" {...props}></Icon>
