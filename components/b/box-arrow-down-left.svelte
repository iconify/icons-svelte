<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/nqhby9b4x.css';
import '../../css/v/vn8zh-asp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><path class="nqhby9b4x"/><path class="vn8zh-asp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:box-arrow-down-left" {...props}></Icon>
