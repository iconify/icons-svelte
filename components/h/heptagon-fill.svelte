<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3f49ybrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m3f49ybrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:heptagon-fill" {...props}></Icon>
