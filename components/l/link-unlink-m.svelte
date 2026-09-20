<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzazjq7mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzazjq7mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:link-unlink-m" {...props}></Icon>
