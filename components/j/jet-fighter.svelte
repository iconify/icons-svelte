<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l61alz7vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l61alz7vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:jet-fighter" {...props}></Icon>
