<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fizh9bcok.css';
import '../../css/b/bi4bqnltf.css';
import '../../css/g/ga2g5dbmp.css';
import '../../css/g/gnp00z80k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fizh9bcok"/><path class="bi4bqnltf"/><path class="ga2g5dbmp"/><path class="gnp00z80k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-flow-20" {...props}></Icon>
