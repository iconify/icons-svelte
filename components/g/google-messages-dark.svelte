<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nim0ecb_g.css';
import '../../css/u/uio7vmi8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nim0ecb_g"/><path class="uio7vmi8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-messages-dark" {...props}></Icon>
