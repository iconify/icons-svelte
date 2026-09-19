<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9ock4bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w9ock4bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:battery-plus" {...props}></Icon>
