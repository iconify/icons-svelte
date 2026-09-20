<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx-12vb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gx-12vb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:music-note-off-2-solid" {...props}></Icon>
