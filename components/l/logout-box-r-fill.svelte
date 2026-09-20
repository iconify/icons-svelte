<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5c5z8huf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5c5z8huf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:logout-box-r-fill" {...props}></Icon>
