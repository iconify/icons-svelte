<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1tvdnb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o1tvdnb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:digg" {...props}></Icon>
