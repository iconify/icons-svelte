<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu8hv6hob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu8hv6hob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:pyramid-filled" {...props}></Icon>
