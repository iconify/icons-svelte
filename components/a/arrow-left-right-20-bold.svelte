<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk6drtbrj.css';
import '../../css/t/t2iyet0dj.css';
import '../../css/g/ga8o6nb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xk6drtbrj"/><path class="t2iyet0dj"/><path class="ga8o6nb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-left-right-20-bold" {...props}></Icon>
