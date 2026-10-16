<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luddyjg5s.css';
import '../../css/z/z2o7skw1w.css';
import '../../css/y/yhu9-56ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="luddyjg5s"/><path class="z2o7skw1w"/><path class="yhu9-56ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-incoming-20-bold" {...props}></Icon>
