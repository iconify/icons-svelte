<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu5wnmgll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pu5wnmgll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lynx-head" {...props}></Icon>
