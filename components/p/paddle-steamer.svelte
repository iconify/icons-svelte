<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdwvp9b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hdwvp9b-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:paddle-steamer" {...props}></Icon>
