<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1vewfb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":16};
const content = `<path class="x1vewfb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:play" {...props}></Icon>
