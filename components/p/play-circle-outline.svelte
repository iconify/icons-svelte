<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv_brepse.css';
import '../../css/j/jwatnmbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yv_brepse"/><path class="jwatnmbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:play-circle-outline" {...props}></Icon>
