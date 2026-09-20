<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sps-9q4ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sps-9q4ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:radarr-anime-light" {...props}></Icon>
