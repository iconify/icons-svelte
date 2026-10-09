<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm5htjbev.css';
import '../../css/u/u247rkkct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tm5htjbev"/><path class="u247rkkct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electrolyser-20-bold" {...props}></Icon>
