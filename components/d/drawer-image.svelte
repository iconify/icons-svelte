<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i339vabyb.css';
import '../../css/g/gtfr4-buh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i339vabyb"/><path class="gtfr4-buh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:drawer-image" {...props}></Icon>
