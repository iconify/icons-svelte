<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twoz65bta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="twoz65bta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:round-straw-bale" {...props}></Icon>
