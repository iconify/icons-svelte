<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znuit7wvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="znuit7wvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-alt-waning-crescent-6" {...props}></Icon>
