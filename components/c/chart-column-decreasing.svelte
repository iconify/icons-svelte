<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyd1r-evo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyd1r-evo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-column-decreasing" {...props}></Icon>
