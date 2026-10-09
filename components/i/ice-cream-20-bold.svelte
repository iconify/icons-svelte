<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbhs844iu.css';
import '../../css/v/vpa9dcbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gbhs844iu"/><path class="vpa9dcbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ice-cream-20-bold" {...props}></Icon>
