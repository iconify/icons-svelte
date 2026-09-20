<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr0lscbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr0lscbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-3-fill" {...props}></Icon>
