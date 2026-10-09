<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6dgzbb5r.css';
import '../../css/j/jd4w5xjrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i6dgzbb5r"/><path class="jd4w5xjrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-container-20-bold" {...props}></Icon>
