<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl9l-cbsp.css';
import '../../css/p/pejn30ben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl9l-cbsp"/><path class="pejn30ben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:network-signal-bold" {...props}></Icon>
