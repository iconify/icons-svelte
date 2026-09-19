<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze76x5b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ze76x5b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:code" {...props}></Icon>
