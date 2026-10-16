<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5t6ee0li.css';
import '../../css/c/c68i7abad.css';
import '../../css/v/vbv9yn3af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a5t6ee0li"/><path class="c68i7abad"/><path class="vbv9yn3af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lawnmower-20" {...props}></Icon>
