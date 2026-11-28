<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1x3a2bvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="h1x3a2bvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bookmark-simple-slash-fill" {...props}></Icon>
