<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro5yrac-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ro5yrac-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:object" {...props}></Icon>
