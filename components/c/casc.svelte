<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxn7l67aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vxn7l67aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:casc" {...props}></Icon>
