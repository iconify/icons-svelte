<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq1pystjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq1pystjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-2-fill" {...props}></Icon>
