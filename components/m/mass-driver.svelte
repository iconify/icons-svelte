<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as6chiboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="as6chiboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mass-driver" {...props}></Icon>
