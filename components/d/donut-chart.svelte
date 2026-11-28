<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdcn0mt7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdcn0mt7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:donut-chart" {...props}></Icon>
