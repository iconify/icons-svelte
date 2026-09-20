<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/n/nxtylxbax.css';
import '../../css/g/gxf7-0b7r.css';
import '../../css/m/msxn8u5pj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nxtylxbax"/><path class="gxf7-0b7r"/><path class="msxn8u5pj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:qr-code-sharp-two-tone" {...props}></Icon>
