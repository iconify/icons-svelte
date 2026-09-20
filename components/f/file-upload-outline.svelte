<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jps7tfbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jps7tfbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-upload-outline" {...props}></Icon>
