<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n85pmxy0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n85pmxy0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:horse-variant" {...props}></Icon>
