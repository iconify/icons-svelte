<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo8dku97l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo8dku97l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:aspect-ratio-line" {...props}></Icon>
