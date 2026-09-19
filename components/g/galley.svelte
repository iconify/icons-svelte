<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy8g0pbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fy8g0pbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:galley" {...props}></Icon>
