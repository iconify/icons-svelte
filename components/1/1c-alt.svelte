<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsak5lzio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wsak5lzio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:1c-alt" {...props}></Icon>
