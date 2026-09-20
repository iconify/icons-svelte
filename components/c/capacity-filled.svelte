<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjjvgvbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sjjvgvbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:capacity-filled" {...props}></Icon>
