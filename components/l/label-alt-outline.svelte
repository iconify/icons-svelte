<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8bblxhcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":384};
const content = `<path class="w8bblxhcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:label-alt-outline" {...props}></Icon>
