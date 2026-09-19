<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbo6mfjnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbo6mfjnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:download" {...props}></Icon>
