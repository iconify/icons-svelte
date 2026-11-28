<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtu-opbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mtu-opbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bookmark-simple-slash-thin" {...props}></Icon>
