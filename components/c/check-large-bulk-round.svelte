<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuoq_xbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuoq_xbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:check-large-bulk-round" {...props}></Icon>
