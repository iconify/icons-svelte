<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm7u26bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="xm7u26bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-waxing-6" {...props}></Icon>
