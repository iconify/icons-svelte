<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/k/kpi2fzh0j.css';
import '../../css/b/b0h_shk9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="n1lsf0bnc"><path class="kpi2fzh0j"/><path class="b0h_shk9a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:dtr" {...props}></Icon>
