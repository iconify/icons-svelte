<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub8jcwb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ub8jcwb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:i-beam-20-bold" {...props}></Icon>
