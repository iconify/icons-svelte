<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/reaq22bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="reaq22bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dripping-goo" {...props}></Icon>
