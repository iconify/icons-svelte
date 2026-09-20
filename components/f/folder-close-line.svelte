<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-hl0zbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-hl0zbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-close-line" {...props}></Icon>
