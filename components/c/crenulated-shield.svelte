<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uayu3q91h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uayu3q91h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crenulated-shield" {...props}></Icon>
