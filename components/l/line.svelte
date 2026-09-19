<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy7a12bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1728};
const content = `<path class="vy7a12bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:line" {...props}></Icon>
