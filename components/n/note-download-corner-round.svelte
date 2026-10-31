<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esa6zfg6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esa6zfg6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-download-corner-round" {...props}></Icon>
