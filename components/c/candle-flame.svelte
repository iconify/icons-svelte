<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuky2vbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zuky2vbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:candle-flame" {...props}></Icon>
