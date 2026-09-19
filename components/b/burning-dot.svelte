<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9ki65buh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p9ki65buh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:burning-dot" {...props}></Icon>
