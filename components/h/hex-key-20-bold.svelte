<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmrel0uvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dmrel0uvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hex-key-20-bold" {...props}></Icon>
