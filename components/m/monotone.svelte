<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r10w3649d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":415,"height":512};
const content = `<path class="r10w3649d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:monotone" {...props}></Icon>
