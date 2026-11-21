<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qefm_s0ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qefm_s0ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-after-effects-dark" {...props}></Icon>
