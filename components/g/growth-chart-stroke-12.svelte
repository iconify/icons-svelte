<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdxs57r6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vdxs57r6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:growth-chart-stroke-12" {...props}></Icon>
