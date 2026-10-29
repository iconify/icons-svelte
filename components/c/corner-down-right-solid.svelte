<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxgi9p8-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxgi9p8-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:corner-down-right-solid" {...props}></Icon>
