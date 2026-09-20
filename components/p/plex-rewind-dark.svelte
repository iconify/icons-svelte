<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkh-nabnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gkh-nabnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plex-rewind-dark" {...props}></Icon>
