<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/ti43njbxy.css';
import '../../css/u/uwvkzmbgi.css';
import '../../css/c/cygy2y6yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ti43njbxy"/><path class="uwvkzmbgi"/><path class="cygy2y6yc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-unlock-01" {...props}></Icon>
