<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt6thsbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="rt6thsbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:file-sound-o" {...props}></Icon>
