<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j37pk-bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j37pk-bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chewed-skull" {...props}></Icon>
