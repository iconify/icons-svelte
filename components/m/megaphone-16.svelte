<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4gg_shhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p4gg_shhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:megaphone-16" {...props}></Icon>
