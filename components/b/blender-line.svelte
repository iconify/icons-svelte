<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx8qa3b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx8qa3b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:blender-line" {...props}></Icon>
