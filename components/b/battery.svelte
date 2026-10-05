<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/u/uf0o_xbbb.css';
import '../../css/h/huci4xpnw.css';
import '../../css/u/uhxc-vbch.css';
import '../../css/m/mmaumbclu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="uf0o_xbbb"/><path class="huci4xpnw"/><path class="uhxc-vbch"/><path class="mmaumbclu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:battery" {...props}></Icon>
