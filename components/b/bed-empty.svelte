<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dem4o0bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dem4o0bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bed-empty" {...props}></Icon>
