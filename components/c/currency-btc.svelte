<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyzk63bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyzk63bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:currency-btc" {...props}></Icon>
