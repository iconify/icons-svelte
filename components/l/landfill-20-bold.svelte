<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9mh0ybkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g9mh0ybkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:landfill-20-bold" {...props}></Icon>
