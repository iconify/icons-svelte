<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fens4lu3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fens4lu3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:line-chart-arrow-down" {...props}></Icon>
