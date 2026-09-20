<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps8b0vb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ps8b0vb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:guardian-plex-light" {...props}></Icon>
