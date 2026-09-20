<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byxbbwb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="byxbbwb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:graph-bar" {...props}></Icon>
