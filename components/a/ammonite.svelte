<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1c5jzgok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z1c5jzgok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ammonite" {...props}></Icon>
