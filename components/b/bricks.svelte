<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8fx0t0nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8fx0t0nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:bricks" {...props}></Icon>
