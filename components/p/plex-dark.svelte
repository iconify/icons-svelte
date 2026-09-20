<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddbgcni7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ddbgcni7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plex-dark" {...props}></Icon>
