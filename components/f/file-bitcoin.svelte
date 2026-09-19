<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/phqllkbbt.css';
import '../../css/y/yp4dgwzus.css';
import '../../css/r/rl4zu8qob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="phqllkbbt"/><path class="yp4dgwzus"/><path class="rl4zu8qob"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-bitcoin" {...props}></Icon>
