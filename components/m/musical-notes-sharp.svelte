<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guw97hb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="guw97hb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:musical-notes-sharp" {...props}></Icon>
