<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddw7wxkey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ddw7wxkey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:drakkar" {...props}></Icon>
