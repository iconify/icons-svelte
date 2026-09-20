<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl9cvpbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl9cvpbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brackets-contain-start" {...props}></Icon>
