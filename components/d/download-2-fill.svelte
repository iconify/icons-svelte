<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxive-lrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxive-lrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:download-2-fill" {...props}></Icon>
