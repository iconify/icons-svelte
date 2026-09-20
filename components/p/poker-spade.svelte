<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax-ov7ovr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax-ov7ovr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:poker-spade" {...props}></Icon>
