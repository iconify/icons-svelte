<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2owjgb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d2owjgb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-xml" {...props}></Icon>
