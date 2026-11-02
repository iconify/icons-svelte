<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvb0gpb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvb0gpb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-bottom-fill" {...props}></Icon>
