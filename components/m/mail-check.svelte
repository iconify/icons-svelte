<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/w/wfsf9hbwi.css';
import '../../css/m/mhx2flpsr.css';
import '../../css/c/c3u021bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="wfsf9hbwi"/><path class="mhx2flpsr"/><path class="c3u021bbk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:mail-check" {...props}></Icon>
