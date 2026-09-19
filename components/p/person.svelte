<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_l1bzkkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="r_l1bzkkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:person" {...props}></Icon>
