<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urb3y9b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="urb3y9b6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dough-roller" {...props}></Icon>
