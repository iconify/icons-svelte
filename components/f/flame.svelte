<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/senf79cxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="senf79cxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flame" {...props}></Icon>
