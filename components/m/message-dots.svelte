<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5pt1-b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5pt1-b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-dots" {...props}></Icon>
