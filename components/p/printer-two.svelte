<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/x/xsydfnbew.css';
import '../../css/o/o39sc1brf.css';
import '../../css/a/awjiwzbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="xsydfnbew"/><rect class="o39sc1brf"/><path class="awjiwzbtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:printer-two" {...props}></Icon>
