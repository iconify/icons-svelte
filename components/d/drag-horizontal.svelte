<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnr7vfbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnr7vfbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:drag-horizontal" {...props}></Icon>
