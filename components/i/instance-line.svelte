<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcgt_7b2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcgt_7b2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:instance-line" {...props}></Icon>
