<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q32_3-bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q32_3-bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hearing-accessibility-symbol" {...props}></Icon>
