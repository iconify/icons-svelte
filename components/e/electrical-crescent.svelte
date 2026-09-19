<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znca9pbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="znca9pbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:electrical-crescent" {...props}></Icon>
