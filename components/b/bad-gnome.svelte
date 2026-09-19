<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n54h2kbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n54h2kbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bad-gnome" {...props}></Icon>
