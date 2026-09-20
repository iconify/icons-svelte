<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is_njbszx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="is_njbszx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:music-note-circle-solid" {...props}></Icon>
