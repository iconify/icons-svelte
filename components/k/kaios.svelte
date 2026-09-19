<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9780c6bs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u9780c6bs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:kaios" {...props}></Icon>
