<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q4ah8fbsm.css';
import '../../css/y/yyru89eax.css';
import '../../css/k/kgl-8sirp.css';
import '../../css/a/ain1tnbxt.css';
import '../../css/s/sy7kpcbuo.css';
import '../../css/m/miknsv_yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q4ah8fbsm wm-k"/><path class="wm-s yyru89eax"/><path class="kgl-8sirp wm-shadow"/><path class="ain1tnbxt wm-k"/><path class="sy7kpcbuo wm-a"/><path class="miknsv_yb wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:image-plus-engrave" {...props}></Icon>
