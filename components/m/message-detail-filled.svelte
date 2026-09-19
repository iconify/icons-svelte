<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slxefw72b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slxefw72b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-detail-filled" {...props}></Icon>
