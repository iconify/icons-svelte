<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4li52eld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4li52eld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-bar-stacked-line" {...props}></Icon>
