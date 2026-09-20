<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw8lq1w4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw8lq1w4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:easyjet" {...props}></Icon>
