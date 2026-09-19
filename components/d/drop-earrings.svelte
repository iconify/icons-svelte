<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu0i6sb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tu0i6sb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:drop-earrings" {...props}></Icon>
