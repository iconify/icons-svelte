<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maggq5byx.css';
import '../../css/p/ph-tdvwvh.css';
import '../../css/d/dz9auwwmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="maggq5byx"/><path class="ph-tdvwvh"/><circle class="dz9auwwmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:mk-4x3" {...props}></Icon>
