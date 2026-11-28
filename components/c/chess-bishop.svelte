<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjnvrp3pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjnvrp3pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:chess-bishop" {...props}></Icon>
