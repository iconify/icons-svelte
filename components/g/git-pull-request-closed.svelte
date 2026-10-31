<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/p/pxm3t__cc.css';
import '../../css/m/mhg49_bwy.css';
import '../../css/e/egzhai3sf.css';
import '../../css/v/v6sn10blx.css';
import '../../css/c/cr4avkb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="pxm3t__cc wm-shadow"/><path class="mhg49_bwy wm-shadow"/><path class="egzhai3sf"/><path class="v6sn10blx"/><path class="cr4avkb_x wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:git-pull-request-closed" {...props}></Icon>
