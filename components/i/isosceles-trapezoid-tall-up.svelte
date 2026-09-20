<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-42yhbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s-42yhbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:isosceles-trapezoid-tall-up" {...props}></Icon>
