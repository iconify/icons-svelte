<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji_hwd0mm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ji_hwd0mm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hanging-spider" {...props}></Icon>
