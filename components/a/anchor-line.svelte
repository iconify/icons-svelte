<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5pp66bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5pp66bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:anchor-line" {...props}></Icon>
