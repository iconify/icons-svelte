<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfv86kbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfv86kbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-download-corner-fill-round" {...props}></Icon>
