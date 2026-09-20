<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/o/oireozd_x.css';
import '../../css/k/k14ve0bcc.css';
import '../../css/s/sp3ujwwyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="oireozd_x"/><path class="k14ve0bcc"/><path class="sp3ujwwyq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bot-sharp-two-tone" {...props}></Icon>
