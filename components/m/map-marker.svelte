<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u148y6bbs.css';
import '../../css/r/re4cghb4q.css';
import '../../css/c/cz14bobdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="u148y6bbs"><path class="re4cghb4q"/><path class="cz14bobdc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:map-marker" {...props}></Icon>
