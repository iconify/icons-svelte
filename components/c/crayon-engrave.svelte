<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v-uycmb5d.css';
import '../../css/k/kgb1ftbgf.css';
import '../../css/r/rfoq9gqca.css';
import '../../css/p/psuc-s3be.css';
import '../../css/w/wlb0b7siw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v-uycmb5d wm-k"/><path class="kgb1ftbgf wm-a"/><path class="rfoq9gqca wm-shadow"/><path class="psuc-s3be wm-k"/><path class="wlb0b7siw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:crayon-engrave" {...props}></Icon>
