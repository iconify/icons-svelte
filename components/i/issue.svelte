<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqd8fcboz.css';
import '../../css/p/p3g2l7o3u.css';
import '../../css/p/pg9erg_-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="hqd8fcboz"><circle class="p3g2l7o3u"/><circle class="pg9erg_-c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gala:issue" {...props}></Icon>
