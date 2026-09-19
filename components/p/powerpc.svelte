<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8m-2300y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l8m-2300y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:powerpc" {...props}></Icon>
