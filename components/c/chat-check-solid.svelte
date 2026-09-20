<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdfs-uwca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdfs-uwca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chat-check-solid" {...props}></Icon>
