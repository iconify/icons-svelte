<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmd0_6_fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="dmd0_6_fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:file-question" {...props}></Icon>
