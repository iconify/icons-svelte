<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es4p5rbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="es4p5rbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:necklace" {...props}></Icon>
