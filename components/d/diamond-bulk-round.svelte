<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vey7pvboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vey7pvboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:diamond-bulk-round" {...props}></Icon>
