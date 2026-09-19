<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr445ngfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sr445ngfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:hjson" {...props}></Icon>
