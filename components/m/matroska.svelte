<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxfnk_byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uxfnk_byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:matroska" {...props}></Icon>
