<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af9xaxben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="af9xaxben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:healing" {...props}></Icon>
