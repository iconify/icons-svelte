<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjb56mchu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cjb56mchu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:burning-embers" {...props}></Icon>
