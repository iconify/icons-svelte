<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/d4vy9ccks.css';
import '../../css/m/mijyx3brl.css';
import '../../css/n/nbiavb01t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="d4vy9ccks"/><path class="mijyx3brl wm-shadow"/><path class="nbiavb01t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:quote-engrave" {...props}></Icon>
