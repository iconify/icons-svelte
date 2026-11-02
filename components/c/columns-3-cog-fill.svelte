<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5tq3cbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5tq3cbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:columns-3-cog-fill" {...props}></Icon>
