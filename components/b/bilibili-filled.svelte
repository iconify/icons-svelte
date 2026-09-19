<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/w/wiea140ii.css';
import '../../css/l/lbse-vh1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<g class="n1lsf0bnc"><path class="wiea140ii"/><path class="lbse-vh1e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:bilibili-filled" {...props}></Icon>
