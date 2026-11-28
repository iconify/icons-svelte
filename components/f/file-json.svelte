<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ema-29wwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ema-29wwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:file-json" {...props}></Icon>
