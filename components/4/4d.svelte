<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp0s8xg3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp0s8xg3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:4d" {...props}></Icon>
