<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/whqs1q3at.css';
import '../../css/z/zkx0jcb5b.css';
import '../../css/x/xbk20hdgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="whqs1q3at"/><path class="wm-k zkx0jcb5b"/><path class="wm-a xbk20hdgs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-stop-sketch" {...props}></Icon>
