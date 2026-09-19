<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8ygnl_-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1280};
const content = `<path class="e8ygnl_-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:chevron-up" {...props}></Icon>
