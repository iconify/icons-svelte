<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn3bqef3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn3bqef3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-download-corner-round" {...props}></Icon>
