<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6u9h6rvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="d6u9h6rvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:bakery-11" {...props}></Icon>
