<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm7p0_b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tm7p0_b_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:paperless-home" {...props}></Icon>
