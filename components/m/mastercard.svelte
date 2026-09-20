<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzm141dva.css';
import '../../css/d/d-spf-bpy.css';
import '../../css/n/ndr05hb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zzm141dva"/><path class="d-spf-bpy"/><path class="ndr05hb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mastercard" {...props}></Icon>
