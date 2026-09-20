<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiw5aogef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiw5aogef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:delete-bin-3-line" {...props}></Icon>
