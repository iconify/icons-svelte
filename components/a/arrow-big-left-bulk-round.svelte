<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wosu6bw4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wosu6bw4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-big-left-bulk-round" {...props}></Icon>
