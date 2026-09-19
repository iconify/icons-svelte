<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvwydsbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mvwydsbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:perfume-bottle" {...props}></Icon>
