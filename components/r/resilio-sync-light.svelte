<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u264_sb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u264_sb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:resilio-sync-light" {...props}></Icon>
