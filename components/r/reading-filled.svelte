<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tni30y4jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tni30y4jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:reading-filled" {...props}></Icon>
