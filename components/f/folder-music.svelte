<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjsa2gbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjsa2gbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-music" {...props}></Icon>
