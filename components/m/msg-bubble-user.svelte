<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/h1xyzvb4l.css';
import '../../css/b/blphqos8l.css';
import '../../css/f/f1tqfuc1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h1xyzvb4l"/><circle class="blphqos8l"/><path class="f1tqfuc1r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:msg-bubble-user" {...props}></Icon>
