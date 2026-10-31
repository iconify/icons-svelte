<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0_57np6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0_57np6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-right-large-bulk-round" {...props}></Icon>
