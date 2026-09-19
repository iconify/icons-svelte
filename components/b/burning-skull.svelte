<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uywq6lb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uywq6lb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:burning-skull" {...props}></Icon>
