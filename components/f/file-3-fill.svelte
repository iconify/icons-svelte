<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swd-e5bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swd-e5bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-3-fill" {...props}></Icon>
