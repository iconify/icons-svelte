<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb32smlnz.css';
import '../../css/t/tznykc51m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vb32smlnz"/><path class="tznykc51m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-conditioning-20-bold" {...props}></Icon>
