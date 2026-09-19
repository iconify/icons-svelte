<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6hl0kb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f6hl0kb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:perspective-dice-six-faces-random" {...props}></Icon>
