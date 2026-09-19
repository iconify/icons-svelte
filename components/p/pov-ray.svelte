<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv8vgf7uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":371,"height":512};
const content = `<path class="rv8vgf7uy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pov-ray" {...props}></Icon>
