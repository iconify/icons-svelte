<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4owv6bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4owv6bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pointing-right-03" {...props}></Icon>
