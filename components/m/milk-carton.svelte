<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylxpa8bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ylxpa8bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:milk-carton" {...props}></Icon>
