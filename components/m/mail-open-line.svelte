<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o27eombkx.css';
import '../../css/s/seq92yhma.css';
import '../../css/e/epwzq1a5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o27eombkx"/><path class="seq92yhma"/><path class="epwzq1a5s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:mail-open-line" {...props}></Icon>
