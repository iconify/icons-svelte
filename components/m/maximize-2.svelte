<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/v/vxl2imb0t.css';
import '../../css/o/ope1nybbx.css';
import '../../css/x/xg3f7vrci.css';
import '../../css/a/ajpm3vd2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="vxl2imb0t wm-shadow"/><path class="ope1nybbx wm-shadow"/><path class="xg3f7vrci"/><path class="ajpm3vd2r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:maximize-2" {...props}></Icon>
