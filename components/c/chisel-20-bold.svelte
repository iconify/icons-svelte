<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbmu3eofk.css';
import '../../css/q/qg7yfsbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jbmu3eofk"/><path class="qg7yfsbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chisel-20-bold" {...props}></Icon>
