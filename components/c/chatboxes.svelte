<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqkz2q7yx.css';
import '../../css/w/wyaou_efh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dqkz2q7yx"/><path class="wyaou_efh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chatboxes" {...props}></Icon>
