<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yffa5ib7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="yffa5ib7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:check-circle-multiple-thin" {...props}></Icon>
