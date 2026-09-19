<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaufy1uke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iaufy1uke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:allied-star" {...props}></Icon>
