<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/j9wrs-0li.css';
import '../../css/n/nby3u7buh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j9wrs-0li"/><path class="nby3u7buh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chart-candlestick" {...props}></Icon>
