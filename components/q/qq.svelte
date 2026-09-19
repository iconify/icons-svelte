<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn0_a_b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="zn0_a_b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:qq" {...props}></Icon>
