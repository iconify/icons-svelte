<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5wi-ryfk.css';
import '../../css/n/nwfb1ibqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5wi-ryfk"/><path class="nwfb1ibqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-alarm-add" {...props}></Icon>
