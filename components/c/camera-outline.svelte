<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2vpa7-wx.css';
import '../../css/q/q_r9obkld.css';
import '../../css/f/fnfrkrn2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h2vpa7-wx"/><circle class="q_r9obkld"/><path class="fnfrkrn2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:camera-outline" {...props}></Icon>
