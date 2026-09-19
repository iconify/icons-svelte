<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgd8_wbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dgd8_wbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gear-hammer" {...props}></Icon>
