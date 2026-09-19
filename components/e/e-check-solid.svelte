<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydnkg5bxq.css';
import '../../css/a/abzcb78fh.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 ydnkg5bxq"/><path class="abzcb78fh clr-i-solid clr-i-solid-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:e-check-solid" {...props}></Icon>
