<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkrbogxng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zkrbogxng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:justice-star" {...props}></Icon>
