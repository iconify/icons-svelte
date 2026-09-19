<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4fzrkbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j4fzrkbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pirate-flag" {...props}></Icon>
