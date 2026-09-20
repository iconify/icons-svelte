<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt367vgwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zt367vgwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jitsi-meet-light" {...props}></Icon>
