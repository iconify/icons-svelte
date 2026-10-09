<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfdja4b-d.css';
import '../../css/n/n8f3jmq8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yfdja4b-d"/><path class="n8f3jmq8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flame-20-bold" {...props}></Icon>
