<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfdk9o7_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jfdk9o7_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:dafny" {...props}></Icon>
