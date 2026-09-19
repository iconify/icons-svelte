<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcos6abkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fcos6abkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-4-spades" {...props}></Icon>
