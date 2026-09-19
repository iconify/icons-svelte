<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a238j-m3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a238j-m3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:arrow-left" {...props}></Icon>
