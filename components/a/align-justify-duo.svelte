<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj7gvbxkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="jj7gvbxkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:align-justify-duo" {...props}></Icon>
