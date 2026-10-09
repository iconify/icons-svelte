<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p92x1lbfk.css';
import '../../css/x/x5bwyrbir.css';
import '../../css/x/xundq6axq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p92x1lbfk"/><path class="x5bwyrbir"/><path class="xundq6axq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ozone-20-bold" {...props}></Icon>
