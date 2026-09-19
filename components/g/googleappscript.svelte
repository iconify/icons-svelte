<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xte2y8b6s.css';
import '../../css/y/ygqhxjblw.css';
import '../../css/s/stpu0nbcx.css';
import '../../css/o/ob2lfwuos.css';
import '../../css/z/zu7l1lbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xte2y8b6s"/><path class="ygqhxjblw"/><path class="stpu0nbcx"/><path class="ob2lfwuos"/><path class="zu7l1lbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:googleappscript" {...props}></Icon>
