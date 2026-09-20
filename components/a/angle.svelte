<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/g/g7agmsbue.css';
import '../../css/z/zqmh3wbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="g7agmsbue"/><path class="zqmh3wbjj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:angle" {...props}></Icon>
