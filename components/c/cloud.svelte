<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyra8pbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="gyra8pbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:cloud" {...props}></Icon>
