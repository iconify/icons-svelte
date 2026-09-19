<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov4q4xpyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ov4q4xpyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-3-diamonds" {...props}></Icon>
