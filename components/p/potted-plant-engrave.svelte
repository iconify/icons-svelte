<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sui2dub7k.css';
import '../../css/m/mjzx30xzu.css';
import '../../css/l/lqb931lgw.css';
import '../../css/h/hlw3r33xs.css';
import '../../css/y/yjt7y95ow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sui2dub7k wm-k"/><path class="mjzx30xzu wm-a"/><path class="lqb931lgw wm-shadow"/><path class="hlw3r33xs wm-k"/><path class="wm-a yjt7y95ow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:potted-plant-engrave" {...props}></Icon>
