<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb2p06bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xb2p06bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:folder-off-solid" {...props}></Icon>
