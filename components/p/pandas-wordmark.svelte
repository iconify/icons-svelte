<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glc6tuupn.css';
import '../../css/g/gx_0y1b1g.css';
import '../../css/x/xhsp1sb3q.css';
import '../../css/o/o84t4kbli.css';
import '../../css/f/fc64knnzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="glc6tuupn"/><path class="gx_0y1b1g"/><path class="xhsp1sb3q"/><path class="o84t4kbli"/><path class="fc64knnzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:pandas-wordmark" {...props}></Icon>
