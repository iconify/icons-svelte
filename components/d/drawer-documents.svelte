<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhbtcways.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yhbtcways"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:drawer-documents" {...props}></Icon>
