<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/k/k56zh769s.css';
import '../../css/u/um227vekh.css';
import '../../css/t/tm9f74uep.css';
import '../../css/j/j2m8g8spq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="k56zh769s"/><path class="um227vekh"/><circle class="tm9f74uep"/><path class="j2m8g8spq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:folder" {...props}></Icon>
