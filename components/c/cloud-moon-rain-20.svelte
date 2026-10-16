<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz-fvxbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yz-fvxbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-moon-rain-20" {...props}></Icon>
