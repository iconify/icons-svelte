<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps4e3y-ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ps4e3y-ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crosshair" {...props}></Icon>
