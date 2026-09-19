<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx371419d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bx371419d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-9-clubs" {...props}></Icon>
