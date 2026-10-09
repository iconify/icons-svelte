<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfl834tqx.css';
import '../../css/j/j77zeoa7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gfl834tqx"/><path class="j77zeoa7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-route-20-bold" {...props}></Icon>
