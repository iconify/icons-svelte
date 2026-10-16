<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqiq30b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aqiq30b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-rock-20-bold" {...props}></Icon>
