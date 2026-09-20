<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdnenkl9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zdnenkl9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-audio-solid" {...props}></Icon>
