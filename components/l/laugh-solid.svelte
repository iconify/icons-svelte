<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdcg-32fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdcg-32fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:laugh-solid" {...props}></Icon>
