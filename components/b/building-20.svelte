<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpt327yfs.css';
import '../../css/t/tbow3qh2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gpt327yfs"/><path class="tbow3qh2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:building-20" {...props}></Icon>
