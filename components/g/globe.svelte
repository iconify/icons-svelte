<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/d/dkbc58bxi.css';
import '../../css/h/hw1hnsbxh.css';
import '../../css/h/h3zgu7-gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="dkbc58bxi"/><path clip-rule="evenodd" class="hw1hnsbxh"/><path class="h3zgu7-gy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:globe" {...props}></Icon>
