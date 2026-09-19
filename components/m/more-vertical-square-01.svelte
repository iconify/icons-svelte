<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztu35ibxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztu35ibxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:more-vertical-square-01" {...props}></Icon>
