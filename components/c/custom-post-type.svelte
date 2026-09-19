<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5j5exdpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5j5exdpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:custom-post-type" {...props}></Icon>
