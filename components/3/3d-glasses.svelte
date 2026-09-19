<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cugzcmbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cugzcmbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:3d-glasses" {...props}></Icon>
