<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5dgtbn3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5dgtbn3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:recycle" {...props}></Icon>
