<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxs5gckpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxs5gckpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-question-mark-filled" {...props}></Icon>
