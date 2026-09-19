<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlx_pfbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="rlx_pfbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:edit-page" {...props}></Icon>
