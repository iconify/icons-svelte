<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjkovvngb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qjkovvngb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:amber-mosquito" {...props}></Icon>
