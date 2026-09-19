<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-dig_o-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n-dig_o-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:armor-upgrade" {...props}></Icon>
