<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb0u8i0od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb0u8i0od"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:presentation" {...props}></Icon>
