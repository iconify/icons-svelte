<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq6pcfb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nq6pcfb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:pie-chart" {...props}></Icon>
