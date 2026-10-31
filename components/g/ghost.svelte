<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/d/dydj80b_d.css';
import '../../css/m/mh9_xvp4g.css';
import '../../css/u/uw0unpbfy.css';
import '../../css/k/k5ujm-b2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="dydj80b_d wm-shadow"/><path class="mh9_xvp4g wm-shadow"/><path class="uw0unpbfy"/><path class="k5ujm-b2k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:ghost" {...props}></Icon>
