<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgbaqzbcl.css';
import '../../css/y/yurlis35z.css';
import '../../css/e/efp1h8bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mgbaqzbcl"/><path class="yurlis35z"/><path class="efp1h8bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailrise-dark" {...props}></Icon>
