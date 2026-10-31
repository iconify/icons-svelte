<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-r9umawa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-r9umawa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-w-bulk-round" {...props}></Icon>
