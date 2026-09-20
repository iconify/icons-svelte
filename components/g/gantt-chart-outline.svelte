<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c29l7mb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c29l7mb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:gantt-chart-outline" {...props}></Icon>
