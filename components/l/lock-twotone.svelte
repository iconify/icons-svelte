<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh0_ewbrk.css';
import '../../css/b/bwbmeku4p.css';
import '../../css/y/yp5ecdcuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sh0_ewbrk"/><path class="bwbmeku4p"/><path class="yp5ecdcuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:lock-twotone" {...props}></Icon>
