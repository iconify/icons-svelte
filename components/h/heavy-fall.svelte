<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfm-fdbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yfm-fdbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heavy-fall" {...props}></Icon>
