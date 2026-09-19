<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/x39l6x9li.css';
import '../../css/i/i036dddnr.css';
import '../../css/w/wwtd6-bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x39l6x9li"/><path class="i036dddnr"/><path class="wwtd6-bsg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:credit-card-not-found" {...props}></Icon>
