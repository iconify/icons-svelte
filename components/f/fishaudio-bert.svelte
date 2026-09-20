<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx5d-bc1s.css';
import '../../css/a/ak6y2c_dv.css';
import '../../css/m/mw_7fybnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nx5d-bc1s"><path class="ak6y2c_dv"/><path class="mw_7fybnk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fishaudio-bert" {...props}></Icon>
