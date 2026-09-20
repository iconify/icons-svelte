<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy3r6pbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gy3r6pbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gull" {...props}></Icon>
