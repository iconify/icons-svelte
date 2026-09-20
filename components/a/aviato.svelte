<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8_wgcx8k.css';
import '../../css/t/t1ypfb_hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i8_wgcx8k"/><path class="t1ypfb_hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aviato" {...props}></Icon>
