<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-h8ahbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p-h8ahbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:m-t-bank" {...props}></Icon>
