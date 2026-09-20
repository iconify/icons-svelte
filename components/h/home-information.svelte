<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_v_pfbhf.css';
import '../../css/j/jkpsqcvpy.css';
import '../../css/n/nux0isb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e_v_pfbhf"/><path class="jkpsqcvpy"/><path class="nux0isb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:home-information" {...props}></Icon>
