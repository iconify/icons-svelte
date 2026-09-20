<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx_p-mb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gx_p-mb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mechanic" {...props}></Icon>
