<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu96an5_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="iu96an5_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:copy" {...props}></Icon>
