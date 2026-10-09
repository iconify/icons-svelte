<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r56gtfh8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r56gtfh8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-lightning-20-bold" {...props}></Icon>
