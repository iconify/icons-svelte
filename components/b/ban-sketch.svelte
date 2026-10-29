<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bksvuqoix.css';
import '../../css/w/wn6sq5bdr.css';
import '../../css/z/zoi-i9f3r.css';
import '../../css/s/s_8u5ojaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bksvuqoix"/><path class="wm-k wn6sq5bdr"/><path class="wm-k zoi-i9f3r"/><path class="s_8u5ojaz wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ban-sketch" {...props}></Icon>
