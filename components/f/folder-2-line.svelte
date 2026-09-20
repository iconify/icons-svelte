<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeke05bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zeke05bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-2-line" {...props}></Icon>
