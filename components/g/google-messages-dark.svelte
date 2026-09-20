<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nim0ecb_g.css';
import '../../css/m/m2lf37b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nim0ecb_g"/><path class="m2lf37b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-messages-dark" {...props}></Icon>
