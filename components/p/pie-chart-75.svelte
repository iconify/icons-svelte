<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twdnls6-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twdnls6-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:pie-chart-75" {...props}></Icon>
