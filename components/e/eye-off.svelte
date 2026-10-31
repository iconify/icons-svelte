<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/m/mv13hkb7j.css';
import '../../css/a/apqyakjsb.css';
import '../../css/o/oqburxzbi.css';
import '../../css/r/rr8yufi7o.css';
import '../../css/v/vvx5zcbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="mv13hkb7j wm-shadow"/><path class="apqyakjsb wm-shadow"/><path class="oqburxzbi"/><path class="rr8yufi7o"/><path class="vvx5zcbvx wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:eye-off" {...props}></Icon>
