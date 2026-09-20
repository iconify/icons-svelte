<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d265mubdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d265mubdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:floppy" {...props}></Icon>
