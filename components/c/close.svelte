<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9j3-mbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b9j3-mbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:close" {...props}></Icon>
