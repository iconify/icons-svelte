<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hng45_bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hng45_bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:captions-off-line" {...props}></Icon>
