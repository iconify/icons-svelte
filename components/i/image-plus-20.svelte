<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4qtxib2o.css';
import '../../css/w/w1mbzmb-x.css';
import '../../css/y/y4i3220kc.css';
import '../../css/z/zkdyo_ief.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k4qtxib2o"/><path class="w1mbzmb-x"/><path class="y4i3220kc"/><path class="zkdyo_ief"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:image-plus-20" {...props}></Icon>
