<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfkmjbgem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfkmjbgem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:location-share" {...props}></Icon>
