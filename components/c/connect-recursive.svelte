<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh6g29_8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bh6g29_8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:connect-recursive" {...props}></Icon>
