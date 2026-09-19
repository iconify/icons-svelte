<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccekybpeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccekybpeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:pie-chart-alt" {...props}></Icon>
