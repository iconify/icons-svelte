<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpu-0cats.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wpu-0cats"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bar-chart-outline" {...props}></Icon>
