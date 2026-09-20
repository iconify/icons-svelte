<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4gewgb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4gewgb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:paint-line" {...props}></Icon>
