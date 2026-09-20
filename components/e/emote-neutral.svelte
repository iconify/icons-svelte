<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0ks-cr2h.css';
import '../../css/b/bhg-vwbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="d0ks-cr2h"/><path class="bhg-vwbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:emote-neutral" {...props}></Icon>
