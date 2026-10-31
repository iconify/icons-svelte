<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7a5fxbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7a5fxbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:microphone-fill-round" {...props}></Icon>
