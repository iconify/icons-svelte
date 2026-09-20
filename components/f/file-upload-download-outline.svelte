<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9seyulth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9seyulth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-upload-download-outline" {...props}></Icon>
