<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl1v7pbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pl1v7pbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:meme-search" {...props}></Icon>
