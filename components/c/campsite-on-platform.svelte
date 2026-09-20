<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1r3n6bhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f1r3n6bhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-on-platform" {...props}></Icon>
