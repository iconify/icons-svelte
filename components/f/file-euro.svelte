<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f41w83s2w.css';
import '../../css/r/rl4zu8qob.css';
import '../../css/e/ehx0rebpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f41w83s2w"/><path class="rl4zu8qob"/><path class="ehx0rebpk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-euro" {...props}></Icon>
