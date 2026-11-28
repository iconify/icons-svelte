<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3mzitb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c3mzitb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:postage-stamp-thin" {...props}></Icon>
