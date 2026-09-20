<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl0y-5bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rl0y-5bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:data-transfer-upload" {...props}></Icon>
