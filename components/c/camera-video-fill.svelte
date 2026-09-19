<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbdd1a27x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wbdd1a27x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:camera-video-fill" {...props}></Icon>
