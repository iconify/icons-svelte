<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjo48szol.css';
import '../../css/a/a5r52wb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjo48szol"/><path class="a5r52wb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:buildings-1" {...props}></Icon>
