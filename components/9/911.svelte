<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpy31sbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lpy31sbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:911" {...props}></Icon>
