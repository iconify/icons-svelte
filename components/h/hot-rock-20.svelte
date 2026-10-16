<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-vt4ubfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r-vt4ubfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-rock-20" {...props}></Icon>
