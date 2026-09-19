<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7y5r_amo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k7y5r_amo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:manual-water-pump" {...props}></Icon>
