<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j29l6eqzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j29l6eqzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:life-ring" {...props}></Icon>
