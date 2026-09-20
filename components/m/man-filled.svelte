<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p08cbk-fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p08cbk-fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:man-filled" {...props}></Icon>
