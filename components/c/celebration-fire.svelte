<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy0sv1baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jy0sv1baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:celebration-fire" {...props}></Icon>
