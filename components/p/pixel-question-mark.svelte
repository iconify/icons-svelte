<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn3_wfb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dn3_wfb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-question-mark" {...props}></Icon>
