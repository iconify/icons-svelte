<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnd8sqbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tnd8sqbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:isosceles-trapezoid-tall-down" {...props}></Icon>
