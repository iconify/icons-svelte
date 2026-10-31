<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rttglkhyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rttglkhyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-funnel-gloss" {...props}></Icon>
