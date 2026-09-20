<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfmze4bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hfmze4bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:lap-timer" {...props}></Icon>
