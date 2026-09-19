<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us80_ldaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="us80_ldaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:netlinx" {...props}></Icon>
