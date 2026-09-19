<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-r_n7yft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z-r_n7yft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pterodactylus" {...props}></Icon>
