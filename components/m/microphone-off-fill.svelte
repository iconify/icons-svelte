<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-bb-ol-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z-bb-ol-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:microphone-off-fill" {...props}></Icon>
