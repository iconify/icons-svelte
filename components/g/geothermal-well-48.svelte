<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzh-h4k4i.css';
import '../../css/o/op16wnoyd.css';
import '../../css/k/k81m4nfaf.css';
import '../../css/q/qiusj_lre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jzh-h4k4i"/><path class="op16wnoyd"/><path class="k81m4nfaf"/><path class="qiusj_lre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:geothermal-well-48" {...props}></Icon>
