<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/k/ky8hevb5b.css';
import '../../css/a/ahhqo1b4s.css';
import '../../css/i/icotk-bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ky8hevb5b"/><path class="ahhqo1b4s"/><path class="icotk-bsx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:power-off-sharp-two-tone" {...props}></Icon>
