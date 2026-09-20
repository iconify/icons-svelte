<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8f7pvblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8f7pvblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-arrow-left" {...props}></Icon>
