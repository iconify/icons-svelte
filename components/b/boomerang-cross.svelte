<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr-lwlbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mr-lwlbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:boomerang-cross" {...props}></Icon>
