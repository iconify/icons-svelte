<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyjk9sblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyjk9sblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:paper-fan-gloss" {...props}></Icon>
