<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcism4bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zcism4bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:json5" {...props}></Icon>
