<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hra-0lbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hra-0lbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hazard-sign" {...props}></Icon>
