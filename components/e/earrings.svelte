<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9s6c3bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n9s6c3bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:earrings" {...props}></Icon>
