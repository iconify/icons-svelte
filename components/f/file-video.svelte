<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjikcm-3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jjikcm-3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-video" {...props}></Icon>
