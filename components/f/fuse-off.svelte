<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2nzyh5rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2nzyh5rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fuse-off" {...props}></Icon>
