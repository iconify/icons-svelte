<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvpdrtm6x.css';
import '../../css/k/kgx7jsbsk.css';
import '../../css/x/xak2o0bmu.css';
import '../../css/k/k6sa60boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lvpdrtm6x"/><path class="kgx7jsbsk"/><path class="xak2o0bmu"/><path class="k6sa60boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mail-x-20-bold" {...props}></Icon>
