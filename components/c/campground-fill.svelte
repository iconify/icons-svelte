<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm4rvkc0n.css';
import '../../css/p/p1djqlbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm4rvkc0n"/><path class="p1djqlbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:campground-fill" {...props}></Icon>
