<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/s/sh6lbgc5j.css';
import '../../css/m/mem1epv9o.css';
import '../../css/g/gb8wnryjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="sh6lbgc5j"/><path class="mem1epv9o"/><path class="gb8wnryjx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:canned-fruit" {...props}></Icon>
