<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu9fc8cxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu9fc8cxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:finder-fill" {...props}></Icon>
