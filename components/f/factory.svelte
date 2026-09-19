<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow_br49or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ow_br49or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:factory" {...props}></Icon>
