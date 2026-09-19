<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwwl4pngj.css';
import '../../css/c/c7npnxbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uwwl4pngj"/><path class="c7npnxbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:analytics" {...props}></Icon>
