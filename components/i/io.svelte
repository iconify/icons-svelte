<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z368c8k2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z368c8k2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:io" {...props}></Icon>
