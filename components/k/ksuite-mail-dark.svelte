<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkom64bwh.css';
import '../../css/v/vk7tt5b4s.css';
import '../../css/u/u_l71ebni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lkom64bwh"/><path class="vk7tt5b4s"/><path class="u_l71ebni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-mail-dark" {...props}></Icon>
