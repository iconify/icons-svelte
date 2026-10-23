<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm4netb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm4netb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:message-square-dashed" {...props}></Icon>
