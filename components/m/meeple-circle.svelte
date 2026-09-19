<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usxh3fzft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="usxh3fzft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:meeple-circle" {...props}></Icon>
