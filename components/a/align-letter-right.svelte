<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyxr4_bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyxr4_bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:align-letter-right" {...props}></Icon>
