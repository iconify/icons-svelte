<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p89o0ebth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p89o0ebth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hungary" {...props}></Icon>
