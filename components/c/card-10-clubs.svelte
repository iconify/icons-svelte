<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyl_5zpad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lyl_5zpad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-10-clubs" {...props}></Icon>
