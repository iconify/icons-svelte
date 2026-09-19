<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt-dj8bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt-dj8bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-leaf" {...props}></Icon>
