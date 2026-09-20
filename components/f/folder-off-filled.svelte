<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyu5cbb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyu5cbb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-off-filled" {...props}></Icon>
