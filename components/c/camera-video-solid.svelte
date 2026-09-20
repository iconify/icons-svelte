<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfsl22bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rfsl22bog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:camera-video-solid" {...props}></Icon>
