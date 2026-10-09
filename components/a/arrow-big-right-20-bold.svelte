<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8ldd46pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h8ldd46pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-big-right-20-bold" {...props}></Icon>
