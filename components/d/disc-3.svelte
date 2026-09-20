<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/r/rrfe6rbol.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/x/xhgvo6bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="shu3xdl9q"/><path class="rrfe6rbol"/><circle class="h_tsn8bxt"/><path class="xhgvo6bxh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:disc-3" {...props}></Icon>
