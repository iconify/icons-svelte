<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma1xzssnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ma1xzssnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:donut-chart-outline" {...props}></Icon>
