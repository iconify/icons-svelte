<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryk05ccjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ryk05ccjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:breaking-chain" {...props}></Icon>
