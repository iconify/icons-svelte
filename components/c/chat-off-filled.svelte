<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm22d3dqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mm22d3dqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-off-filled" {...props}></Icon>
