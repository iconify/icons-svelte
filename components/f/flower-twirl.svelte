<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3_r0mbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h3_r0mbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flower-twirl" {...props}></Icon>
