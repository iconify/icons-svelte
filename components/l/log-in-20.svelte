<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbmplvbtr.css';
import '../../css/z/ztnh5ln4w.css';
import '../../css/a/afdw2ab2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sbmplvbtr"/><path class="ztnh5ln4w"/><path class="afdw2ab2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:log-in-20" {...props}></Icon>
