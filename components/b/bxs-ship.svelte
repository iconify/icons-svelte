<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb-99kp1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb-99kp1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-ship" {...props}></Icon>
