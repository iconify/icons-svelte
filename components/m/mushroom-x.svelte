<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4hauzmfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4hauzmfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mushroom-x" {...props}></Icon>
