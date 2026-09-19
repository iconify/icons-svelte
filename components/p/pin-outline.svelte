<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mljob0-zg.css';
import '../../css/f/fs2axpb2l.css';
import '../../css/s/sq5vlkbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="mljob0-zg"/><path class="fs2axpb2l"/><circle class="sq5vlkbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:pin-outline" {...props}></Icon>
