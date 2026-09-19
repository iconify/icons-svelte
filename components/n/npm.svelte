<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylkih6j-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":430,"height":512};
const content = `<path class="ylkih6j-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:npm" {...props}></Icon>
