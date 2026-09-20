<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg3dsid_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg3dsid_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chart-scatter-plot" {...props}></Icon>
