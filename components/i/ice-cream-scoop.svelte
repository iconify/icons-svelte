<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ern829bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ern829bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ice-cream-scoop" {...props}></Icon>
