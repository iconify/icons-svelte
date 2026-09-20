<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vghuicoks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="vghuicoks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:atproto" {...props}></Icon>
