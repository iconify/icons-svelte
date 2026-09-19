<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p541ors4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p541ors4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:kevlar" {...props}></Icon>
