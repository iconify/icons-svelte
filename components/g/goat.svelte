<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spaeb_25g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="spaeb_25g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:goat" {...props}></Icon>
