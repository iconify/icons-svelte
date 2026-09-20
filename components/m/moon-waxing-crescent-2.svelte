<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6vjloltc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="b6vjloltc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-waxing-crescent-2" {...props}></Icon>
