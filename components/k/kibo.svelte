<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2w58mbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i2w58mbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:kibo" {...props}></Icon>
