<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxdmc1b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxdmc1b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fridge-filled-bottom" {...props}></Icon>
