<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v__9k2bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v__9k2bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fishing-net" {...props}></Icon>
