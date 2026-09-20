<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp8cl2adt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp8cl2adt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:download-line" {...props}></Icon>
