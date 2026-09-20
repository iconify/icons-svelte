<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/grqj15bkb.css';
import '../../css/k/k5w-56bxk.css';
import '../../css/d/df1a4kbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="grqj15bkb"/><path class="k5w-56bxk"/><path class="df1a4kbkn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gas-pump" {...props}></Icon>
