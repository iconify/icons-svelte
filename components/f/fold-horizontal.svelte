<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4ttsc5cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4ttsc5cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:fold-horizontal" {...props}></Icon>
