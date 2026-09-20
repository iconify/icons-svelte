<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/y/yqvkmow1r.css';
import '../../css/k/kfw3mq-ct.css';
import '../../css/z/zqtrx1b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="yqvkmow1r"/><path class="kfw3mq-ct"/><path class="zqtrx1b9w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:import" {...props}></Icon>
