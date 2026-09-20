<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2_s-fbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2_s-fbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:campground-line" {...props}></Icon>
