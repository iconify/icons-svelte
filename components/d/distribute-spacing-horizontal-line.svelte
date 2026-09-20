<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9g93yflh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9g93yflh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:distribute-spacing-horizontal-line" {...props}></Icon>
