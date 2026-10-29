<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/godq996fe.css';
import '../../css/w/wxmbpuu5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="godq996fe wm-k"/><path class="wm-a wxmbpuu5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:arrow-up-right" {...props}></Icon>
