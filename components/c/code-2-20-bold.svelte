<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkx8hebbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zkx8hebbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:code-2-20-bold" {...props}></Icon>
