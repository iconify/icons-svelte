<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8h5-2k2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="j8h5-2k2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:ffwd" {...props}></Icon>
