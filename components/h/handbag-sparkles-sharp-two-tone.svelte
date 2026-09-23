<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/i/ian_mmbvf.css';
import '../../css/n/nzp--8blb.css';
import '../../css/o/omi2j1bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ian_mmbvf"/><path class="nzp--8blb"/><path class="omi2j1bhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:handbag-sparkles-sharp-two-tone" {...props}></Icon>
