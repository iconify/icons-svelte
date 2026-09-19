<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jubo05bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<path class="jubo05bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:line-chart" {...props}></Icon>
