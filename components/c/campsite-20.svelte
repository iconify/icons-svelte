<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c259fp7uq.css';
import '../../css/r/rf7gwnj9m.css';
import '../../css/x/xvxiwibyx.css';
import '../../css/v/vzsiftpbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c259fp7uq"/><path class="rf7gwnj9m"/><path class="xvxiwibyx"/><path class="vzsiftpbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:campsite-20" {...props}></Icon>
