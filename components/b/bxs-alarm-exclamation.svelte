<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smx10x8rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smx10x8rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-alarm-exclamation" {...props}></Icon>
