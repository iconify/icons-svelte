<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-cjo9ueo.css';
import '../../css/p/p5oqracae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-cjo9ueo"/><path class="p5oqracae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-line-chart" {...props}></Icon>
