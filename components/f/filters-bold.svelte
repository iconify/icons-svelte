<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oae5odbze.css';
import '../../css/s/stcmdibrh.css';
import '../../css/d/d086ypt1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oae5odbze"/><path class="stcmdibrh"/><path class="d086ypt1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:filters-bold" {...props}></Icon>
