<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/x/x9tlpeb-b.css';
import '../../css/b/bhtzexbvl.css';
import '../../css/m/mu1binbsn.css';
import '../../css/l/lzvy5umxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="wm-shadow x9tlpeb-b"/><path class="bhtzexbvl wm-shadow"/><path class="mu1binbsn"/><path class="lzvy5umxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:basketball" {...props}></Icon>
