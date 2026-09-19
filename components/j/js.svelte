<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abi5rp9im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="abi5rp9im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:js" {...props}></Icon>
