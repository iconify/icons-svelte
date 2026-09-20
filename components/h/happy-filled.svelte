<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv0v1xbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv0v1xbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:happy-filled" {...props}></Icon>
