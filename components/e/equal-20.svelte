<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rplgk-p1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rplgk-p1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:equal-20" {...props}></Icon>
