<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve2w2-b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ve2w2-b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:chart-area" {...props}></Icon>
