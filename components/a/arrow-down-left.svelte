<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qph67wbba.css';
import '../../css/f/fhycmcb-v.css';
import '../../css/f/fb0las6fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qph67wbba wm-shadow"/><path class="fhycmcb-v wm-k"/><path class="fb0las6fs wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:arrow-down-left" {...props}></Icon>
