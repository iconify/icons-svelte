<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvb_mkr1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvb_mkr1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-square-code-gloss" {...props}></Icon>
