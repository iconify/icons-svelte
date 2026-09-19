<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqae0sbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqae0sbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-sultan-lightstrip-off" {...props}></Icon>
