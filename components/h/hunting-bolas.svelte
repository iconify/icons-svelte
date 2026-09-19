<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd4x53h2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fd4x53h2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hunting-bolas" {...props}></Icon>
