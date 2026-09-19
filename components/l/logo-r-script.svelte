<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjw-j4bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gjw-j4bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-r-script" {...props}></Icon>
