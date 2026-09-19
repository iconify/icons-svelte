<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxuo3p-of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1792};
const content = `<path class="jxuo3p-of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:arrows-v" {...props}></Icon>
