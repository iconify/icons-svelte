<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/w/wk51pcbgt.css';
import '../../css/v/vaj17wbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<g class="n1lsf0bnc"><path class="wk51pcbgt"/><path class="vaj17wbut"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:python-outlined" {...props}></Icon>
