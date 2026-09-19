<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/d/drr99_06v.css';
import '../../css/w/whufb0eev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="chart-column-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="drr99_06v"/><path class="whufb0eev"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:chart-column-outline" {...props}></Icon>
