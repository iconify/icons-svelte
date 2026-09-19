<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph9rotbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ph9rotbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:boat-fishing" {...props}></Icon>
