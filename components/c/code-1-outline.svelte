<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-3s45tqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="k-3s45tqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:code-1-outline" {...props}></Icon>
