<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9_fmcj7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b9_fmcj7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-left-from-tall-rectangle-outline" {...props}></Icon>
