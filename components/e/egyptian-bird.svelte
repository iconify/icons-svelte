<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9ijzxows.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u9ijzxows"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:egyptian-bird" {...props}></Icon>
