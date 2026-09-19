<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcy09zexs.css';
import '../../css/v/vani8sbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcy09zexs"/><path class="vani8sbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:pie-chart-outline" {...props}></Icon>
