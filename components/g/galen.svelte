<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w52fp8bxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w52fp8bxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:galen" {...props}></Icon>
