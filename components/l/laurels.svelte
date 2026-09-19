<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2dggi7_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k2dggi7_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:laurels" {...props}></Icon>
