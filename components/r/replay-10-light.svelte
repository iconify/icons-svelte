<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cee5okbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cee5okbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:replay-10-light" {...props}></Icon>
