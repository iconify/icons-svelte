<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3i4-s0jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3i4-s0jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heart-off-line" {...props}></Icon>
