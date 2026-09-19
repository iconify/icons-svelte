<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-06l_p3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":353,"height":512};
const content = `<path class="d-06l_p3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:rexx" {...props}></Icon>
