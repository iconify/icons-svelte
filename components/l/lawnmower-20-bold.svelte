<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zudjy0tbx.css';
import '../../css/t/te4hhac8s.css';
import '../../css/b/bat89cbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zudjy0tbx"/><path class="te4hhac8s"/><path class="bat89cbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lawnmower-20-bold" {...props}></Icon>
