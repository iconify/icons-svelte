<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi-1inbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="zi-1inbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:dumpster" {...props}></Icon>
