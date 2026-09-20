<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe2dg1bnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pe2dg1bnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jellyfin-light" {...props}></Icon>
