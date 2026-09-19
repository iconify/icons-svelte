<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cilqk84vn.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="cilqk84vn clr-i-outline clr-i-outline-path-1"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:cursor-hand-grab-line" {...props}></Icon>
