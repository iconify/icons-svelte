<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5z_ev-up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r5z_ev-up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dog-house" {...props}></Icon>
