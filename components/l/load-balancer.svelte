<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im4cxtbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="im4cxtbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:load-balancer" {...props}></Icon>
