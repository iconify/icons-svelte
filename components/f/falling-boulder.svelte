<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u26p2qdhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u26p2qdhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:falling-boulder" {...props}></Icon>
