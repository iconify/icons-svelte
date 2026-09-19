<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7aog5bof.css';
import '../../css/g/gysnikbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l7aog5bof"/><path class="gysnikbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:camera" {...props}></Icon>
