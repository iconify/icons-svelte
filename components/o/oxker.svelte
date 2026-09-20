<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh0_e8b5g.css';
import '../../css/r/r0v7q4-zh.css';
import '../../css/a/a1c6c_bxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yh0_e8b5g"/><circle class="r0v7q4-zh"/><path class="a1c6c_bxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oxker" {...props}></Icon>
