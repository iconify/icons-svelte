<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtuukp9fe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gtuukp9fe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:meme-search-light" {...props}></Icon>
