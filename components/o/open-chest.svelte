<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tya9mac8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tya9mac8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:open-chest" {...props}></Icon>
