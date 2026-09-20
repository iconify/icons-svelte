<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/x/xirci526l.css';
import '../../css/t/taosqkbwj.css';
import '../../css/h/hm4yo6blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="xirci526l"/><path class="taosqkbwj"/><path class="hm4yo6blt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:fork-git" {...props}></Icon>
