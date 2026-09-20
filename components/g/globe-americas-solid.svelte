<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0sf03b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z0sf03b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:globe-americas-solid" {...props}></Icon>
