<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/yo0duhs6b.css';
import '../../css/l/lww7c4bwc.css';
import '../../css/x/xh77j1kmh.css';
import '../../css/q/qso6odhhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="yo0duhs6b"/><path class="lww7c4bwc"/><path class="xh77j1kmh"/><path class="qso6odhhx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:gate-not" {...props}></Icon>
