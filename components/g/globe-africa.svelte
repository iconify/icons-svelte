<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l80mjvbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l80mjvbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:globe-africa" {...props}></Icon>
