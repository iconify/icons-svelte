<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib478c30h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib478c30h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-horizontal-fill" {...props}></Icon>
