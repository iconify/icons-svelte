<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-gw61byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="g-gw61byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:element-filled" {...props}></Icon>
