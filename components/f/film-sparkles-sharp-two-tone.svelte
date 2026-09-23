<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/v/vzyo6xb_u.css';
import '../../css/s/snibgdcaa.css';
import '../../css/n/nyf2tdbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vzyo6xb_u"/><path class="snibgdcaa"/><path class="nyf2tdbha"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:film-sparkles-sharp-two-tone" {...props}></Icon>
