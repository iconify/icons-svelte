<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-9asxfcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-9asxfcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:grip-horizontal-gloss" {...props}></Icon>
