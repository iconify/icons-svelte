<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewydz64iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ewydz64iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:lightbulb-compact" {...props}></Icon>
