<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a00qgcwyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a00qgcwyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:jump-link" {...props}></Icon>
