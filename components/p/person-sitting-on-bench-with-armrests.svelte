<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a17i5e9cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a17i5e9cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sitting-on-bench-with-armrests" {...props}></Icon>
