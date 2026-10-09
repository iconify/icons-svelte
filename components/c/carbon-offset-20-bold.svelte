<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zle0wgbup.css';
import '../../css/u/uxo-7bbsr.css';
import '../../css/v/vz0osi9vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zle0wgbup"/><path class="uxo-7bbsr"/><path class="vz0osi9vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-offset-20-bold" {...props}></Icon>
