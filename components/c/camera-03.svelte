<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mum8h13xe.css';
import '../../css/l/lr5p17fsb.css';
import '../../css/s/s3rtijlqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mum8h13xe"/><path class="lr5p17fsb"/><path class="s3rtijlqj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:camera-03" {...props}></Icon>
