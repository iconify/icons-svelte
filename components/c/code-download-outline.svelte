<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4ql3x9ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a4ql3x9ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:code-download-outline" {...props}></Icon>
