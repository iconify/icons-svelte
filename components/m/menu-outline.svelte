<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjh0_9b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wjh0_9b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:menu-outline" {...props}></Icon>
