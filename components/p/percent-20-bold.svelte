<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k52a32ocl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k52a32ocl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:percent-20-bold" {...props}></Icon>
