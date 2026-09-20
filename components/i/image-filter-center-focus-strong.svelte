<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfxy0ht-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfxy0ht-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-filter-center-focus-strong" {...props}></Icon>
