<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evs4fibve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="evs4fibve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:reticule" {...props}></Icon>
