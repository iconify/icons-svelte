<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsp2f4jtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dsp2f4jtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cilium-hubble-dark" {...props}></Icon>
