<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjjjb_bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjjjb_bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-upload-line" {...props}></Icon>
