<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it0rrpb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it0rrpb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-right-large-fill-round" {...props}></Icon>
