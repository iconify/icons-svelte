<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ighzsn08w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ighzsn08w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bitcoin-gloss" {...props}></Icon>
