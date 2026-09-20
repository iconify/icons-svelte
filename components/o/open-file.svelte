<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/hb6uocgia.css';
import '../../css/d/dvfmwi3vd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="n1lsf0bnc"><path class="hb6uocgia"/><path class="dvfmwi3vd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:open-file" {...props}></Icon>
