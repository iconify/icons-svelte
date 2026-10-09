<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8lzt5lna.css';
import '../../css/m/mvzjp1byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x8lzt5lna"/><path class="mvzjp1byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:move-vertical-20-bold" {...props}></Icon>
