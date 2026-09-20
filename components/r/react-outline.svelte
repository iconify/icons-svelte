<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/b/bbpy9nbbh.css';
import '../../css/z/zz0yp4bhr.css';
import '../../css/n/n6ytud-wm.css';
import '../../css/t/t308wjbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<g class="h01tyzbfu"><path class="bbpy9nbbh"/><path class="zz0yp4bhr"/><path class="n6ytud-wm"/><path class="t308wjbmr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:react-outline" {...props}></Icon>
