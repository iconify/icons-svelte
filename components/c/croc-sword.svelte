<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp1c67b8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vp1c67b8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:croc-sword" {...props}></Icon>
