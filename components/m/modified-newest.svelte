<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x55r3nbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x55r3nbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:modified-newest" {...props}></Icon>
