<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9zf29bpy.css';
import '../../css/t/tcyc0_hyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a9zf29bpy"/><path class="tcyc0_hyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bar" {...props}></Icon>
