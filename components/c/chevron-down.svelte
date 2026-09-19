<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhm5-k6is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="yhm5-k6is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:chevron-down" {...props}></Icon>
