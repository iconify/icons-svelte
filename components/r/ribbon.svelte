<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6h3ts8be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p6h3ts8be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ribbon" {...props}></Icon>
