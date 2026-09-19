<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amd5b9b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="amd5b9b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:code-climate" {...props}></Icon>
