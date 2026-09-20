<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi4ot5f0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pi4ot5f0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:heart-filled-16" {...props}></Icon>
