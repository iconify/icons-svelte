<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqz3f3blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oqz3f3blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:over-infinity" {...props}></Icon>
