<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbq02_gxn.css';
import '../../css/q/qlu-mbtpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xbq02_gxn"/><path class="qlu-mbtpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-loading-75-percent-1" {...props}></Icon>
