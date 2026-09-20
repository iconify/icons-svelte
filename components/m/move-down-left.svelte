<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppsp0su1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppsp0su1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:move-down-left" {...props}></Icon>
