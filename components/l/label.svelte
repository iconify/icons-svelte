<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9s_-2o4x.css';
import '../../css/t/t93u26bci.css';
import '../../css/d/denr8sb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j9s_-2o4x"/><path class="t93u26bci"/><path class="denr8sb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:label" {...props}></Icon>
