<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo7obrd1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qo7obrd1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:airplane-departure" {...props}></Icon>
