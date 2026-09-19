<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0v0ilbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="l0v0ilbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:file-word-o" {...props}></Icon>
