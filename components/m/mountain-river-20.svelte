<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oruybqb1x.css';
import '../../css/z/z4r98tbta.css';
import '../../css/z/z88o7-bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oruybqb1x"/><path class="z4r98tbta"/><path class="z88o7-bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mountain-river-20" {...props}></Icon>
