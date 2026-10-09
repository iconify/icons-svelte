<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgnfd1b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hgnfd1b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heart-off-20" {...props}></Icon>
