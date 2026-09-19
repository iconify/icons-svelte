<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nob9nfb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nob9nfb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:carousel-vertical" {...props}></Icon>
