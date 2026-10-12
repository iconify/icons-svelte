<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd-ach6mv.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/x/xak2o0bmu.css';
import '../../css/k/k6sa60boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rd-ach6mv"/><path class="aqsnv9bnd"/><path class="xak2o0bmu"/><path class="k6sa60boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-x-20-bold" {...props}></Icon>
