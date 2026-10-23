<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt_gj5bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt_gj5bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:message-square-dot" {...props}></Icon>
