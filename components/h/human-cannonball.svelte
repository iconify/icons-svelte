<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyr4txpno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tyr4txpno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:human-cannonball" {...props}></Icon>
