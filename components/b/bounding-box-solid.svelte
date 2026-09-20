<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by2b1m5vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by2b1m5vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:bounding-box-solid" {...props}></Icon>
