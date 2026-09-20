<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/p/p5q9gt7mp.css';
import '../../css/h/h_19s7bjx.css';
import '../../css/s/shwcvelcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="p5q9gt7mp"/><path class="h_19s7bjx"/><path class="shwcvelcu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message-question-mark-round" {...props}></Icon>
