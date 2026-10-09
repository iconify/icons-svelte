<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4q0sxn6x.css';
import '../../css/p/p-3dudb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y4q0sxn6x"/><path class="p-3dudb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:download-cloud-20-bold" {...props}></Icon>
