<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/guj5ndblb.css';
import '../../css/f/fd641zcer.css';
import '../../css/d/dqh2e367l.css';
import '../../css/g/gcs2nkswg.css';
import '../../css/o/obcs1cbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="guj5ndblb"/><path class="fd641zcer"/><path class="dqh2e367l"/><path class="gcs2nkswg"/><path class="obcs1cbgf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:microphone-3-broken" {...props}></Icon>
