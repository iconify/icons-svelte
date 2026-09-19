<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfrfi7yif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jfrfi7yif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crossed-chains" {...props}></Icon>
