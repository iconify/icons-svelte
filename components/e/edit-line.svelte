<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylc0x0u6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylc0x0u6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:edit-line" {...props}></Icon>
