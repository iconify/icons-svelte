<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw2zl7-aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rw2zl7-aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:guardian-plex" {...props}></Icon>
