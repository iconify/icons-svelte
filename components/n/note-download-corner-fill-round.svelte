<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6nqkob6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6nqkob6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-download-corner-fill-round" {...props}></Icon>
