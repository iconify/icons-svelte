<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey5-szfvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ey5-szfvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:pause-20-solid" {...props}></Icon>
