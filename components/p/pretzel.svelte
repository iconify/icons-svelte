<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry_2hkara.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry_2hkara"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:pretzel" {...props}></Icon>
