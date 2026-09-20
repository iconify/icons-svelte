<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mukbxhbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mukbxhbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:coin" {...props}></Icon>
