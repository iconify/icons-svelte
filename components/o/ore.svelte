<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl29yxbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rl29yxbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ore" {...props}></Icon>
