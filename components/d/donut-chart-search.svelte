<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk2y3hezu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk2y3hezu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:donut-chart-search" {...props}></Icon>
