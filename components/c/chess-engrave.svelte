<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gzjffcpzq.css';
import '../../css/r/rwh3knbhs.css';
import '../../css/p/p81j7dbae.css';
import '../../css/x/xck8kdj3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gzjffcpzq wm-k"/><path class="rwh3knbhs wm-shadow"/><path class="p81j7dbae wm-k"/><path class="wm-a xck8kdj3v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chess-engrave" {...props}></Icon>
