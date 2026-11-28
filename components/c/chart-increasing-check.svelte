<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e98vwsb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e98vwsb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:chart-increasing-check" {...props}></Icon>
