<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joue-ubee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="joue-ubee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:candle-heart" {...props}></Icon>
