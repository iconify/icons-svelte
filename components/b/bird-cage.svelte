<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/corv2ebzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="corv2ebzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bird-cage" {...props}></Icon>
