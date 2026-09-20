<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5mqw_b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m5mqw_b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:pie-chart" {...props}></Icon>
