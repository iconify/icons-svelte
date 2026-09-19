<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnwv1pbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnwv1pbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:pie-chart-50" {...props}></Icon>
