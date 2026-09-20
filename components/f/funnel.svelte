<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elk0dolzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="elk0dolzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:funnel" {...props}></Icon>
