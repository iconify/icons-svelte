<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubs1v_4lx.css';
import '../../css/d/dxhdilb2v.css';
import '../../css/g/g4y8tubxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ubs1v_4lx"/><path class="dxhdilb2v"/><path class="g4y8tubxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gryt-light" {...props}></Icon>
