<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8gl3cc4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w8gl3cc4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:recording-tape-bubble-square-solid" {...props}></Icon>
