<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v0wa9lmog.css';
import '../../css/u/uv6xo5b9m.css';
import '../../css/j/jesj_obln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v0wa9lmog wm-k"/><path class="uv6xo5b9m wm-k"/><path class="jesj_obln wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:popcorn-sketch" {...props}></Icon>
