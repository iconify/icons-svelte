<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi4s_jfku.css';
import '../../css/o/oy44jibka.css';
import '../../css/u/uv4oycn3f.css';
import '../../css/f/f5p3rgbsd.css';
import '../../css/l/lnf8p3bgz.css';
import '../../css/a/aui-jmtcx.css';
import '../../css/x/xnior1bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi4s_jfku"/><path class="oy44jibka"/><path class="uv4oycn3f"/><path class="f5p3rgbsd"/><path class="lnf8p3bgz"/><path class="aui-jmtcx"/><path class="xnior1bog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gamepad-charge-bold-duotone" {...props}></Icon>
