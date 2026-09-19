<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp7iw6bnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cp7iw6bnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lead-pipe" {...props}></Icon>
