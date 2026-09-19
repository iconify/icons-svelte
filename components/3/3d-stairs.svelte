<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iftlmeb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iftlmeb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:3d-stairs" {...props}></Icon>
