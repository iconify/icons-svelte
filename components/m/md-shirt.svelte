<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esd65cbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="esd65cbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-shirt" {...props}></Icon>
