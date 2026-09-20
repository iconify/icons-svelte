<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb4hln.css';
import '../../css/d/d-d0cg1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yb4hln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:pause-to-play-transition" {...props}></Icon>
