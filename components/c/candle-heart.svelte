<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxeuf6tsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxeuf6tsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:candle-heart" {...props}></Icon>
