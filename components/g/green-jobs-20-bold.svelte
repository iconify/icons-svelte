<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh0-6objo.css';
import '../../css/u/u5hzo-bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bh0-6objo"/><path class="u5hzo-bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:green-jobs-20-bold" {...props}></Icon>
