<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew_ugga8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="ew_ugga8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:pig" {...props}></Icon>
