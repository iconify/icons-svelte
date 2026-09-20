<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh6wf76bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh6wf76bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-multiple-image" {...props}></Icon>
