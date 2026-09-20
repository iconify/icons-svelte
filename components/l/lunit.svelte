<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugtg92bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":189,"height":52};
const content = `<path class="ugtg92bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:lunit" {...props}></Icon>
