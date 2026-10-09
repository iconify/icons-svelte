<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrn2qju6o.css';
import '../../css/b/bgn-z-bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hrn2qju6o"/><path class="bgn-z-bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mountain-20-bold" {...props}></Icon>
