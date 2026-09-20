<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9djg6bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g9djg6bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plex-rewind-light" {...props}></Icon>
