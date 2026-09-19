<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfe2s8iii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jfe2s8iii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:grasping-claws" {...props}></Icon>
