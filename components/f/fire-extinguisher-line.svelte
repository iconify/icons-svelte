<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvb0yvbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvb0yvbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fire-extinguisher-line" {...props}></Icon>
