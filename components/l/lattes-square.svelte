<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsu1dvs7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="jsu1dvs7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:lattes-square" {...props}></Icon>
