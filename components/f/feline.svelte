<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgwm3vbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vgwm3vbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:feline" {...props}></Icon>
