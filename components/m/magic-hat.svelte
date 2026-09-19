<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j08hd8boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j08hd8boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:magic-hat" {...props}></Icon>
