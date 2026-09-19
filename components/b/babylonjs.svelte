<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jddk7dbei.css';
import '../../css/k/kb3-99ksi.css';
import '../../css/j/jt1rljkls.css';
import '../../css/g/gve1udbrm.css';
import '../../css/n/nljj-lovt.css';
import '../../css/t/t1z6b6bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cls-3 jddk7dbei"/><path class="cls-1 kb3-99ksi"/><path class="cls-4 jt1rljkls"/><path class="cls-5 gve1udbrm"/><path class="cls-2 nljj-lovt"/><path class="t1z6b6bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:babylonjs" {...props}></Icon>
