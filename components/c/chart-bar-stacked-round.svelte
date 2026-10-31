<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s04gq1kef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s04gq1kef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-bar-stacked-round" {...props}></Icon>
