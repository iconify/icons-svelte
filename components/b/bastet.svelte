<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4s5k1myl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g4s5k1myl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bastet" {...props}></Icon>
