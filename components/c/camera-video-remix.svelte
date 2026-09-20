<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlpl7u3co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nlpl7u3co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:camera-video-remix" {...props}></Icon>
