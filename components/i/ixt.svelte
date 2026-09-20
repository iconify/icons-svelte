<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy29vdbwc.css';
import '../../css/p/p8jj4km5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gy29vdbwc"/><path class="p8jj4km5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ixt" {...props}></Icon>
