<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_4s_ccvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_4s_ccvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mouse-move-vertical" {...props}></Icon>
