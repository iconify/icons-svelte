<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq5ig7bzi.css';
import '../../css/z/zt4ibv4ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jq5ig7bzi"/><path class="zt4ibv4ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:desert-20-bold" {...props}></Icon>
