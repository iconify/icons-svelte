<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d77g6mbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="d77g6mbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:deviantart" {...props}></Icon>
