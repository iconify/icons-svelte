<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkahacbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="vkahacbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:delicious" {...props}></Icon>
