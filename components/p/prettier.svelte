<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuxjtbc2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":439,"height":512};
const content = `<path class="yuxjtbc2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:prettier" {...props}></Icon>
