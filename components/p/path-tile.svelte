<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x77ephd2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x77ephd2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:path-tile" {...props}></Icon>
