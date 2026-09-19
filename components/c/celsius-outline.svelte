<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yq5outbnn.css';
import '../../css/h/h9xdm6kyq.css';
import '../../css/d/dkh8f-qdu.css';
import '../../css/v/vtg6btbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="yq5outbnn"/><path class="h9xdm6kyq"/><path clip-rule="evenodd" class="dkh8f-qdu"/><path class="vtg6btbak"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:celsius-outline" {...props}></Icon>
