<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/guj5ndblb.css';
import '../../css/m/mkwvu5bez.css';
import '../../css/g/gweihee3d.css';
import '../../css/o/obcs1cbgf.css';
import '../../css/g/gcs2nkswg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="guj5ndblb"/><path class="mkwvu5bez"/><path class="gweihee3d"/><path class="obcs1cbgf"/><path class="gcs2nkswg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:microphone-broken" {...props}></Icon>
