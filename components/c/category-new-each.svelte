<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s99tybc2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s99tybc2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:category-new-each" {...props}></Icon>
