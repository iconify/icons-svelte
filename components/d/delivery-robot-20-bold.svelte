<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbk_it7zx.css';
import '../../css/m/m9fufbb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mbk_it7zx"/><path class="m9fufbb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:delivery-robot-20-bold" {...props}></Icon>
