<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybh5y4q9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ybh5y4q9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bullseye" {...props}></Icon>
