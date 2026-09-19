<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsws4ub3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gsws4ub3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flame-spin" {...props}></Icon>
