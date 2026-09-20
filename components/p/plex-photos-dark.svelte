<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujctd5tks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ujctd5tks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plex-photos-dark" {...props}></Icon>
