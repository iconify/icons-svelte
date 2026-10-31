<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f58w969ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f58w969ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-json-gloss" {...props}></Icon>
