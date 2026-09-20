<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrphjs-2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wrphjs-2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:courthouse-14" {...props}></Icon>
