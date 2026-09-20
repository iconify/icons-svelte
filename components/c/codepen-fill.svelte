<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pie-r5bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pie-r5bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:codepen-fill" {...props}></Icon>
