<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv_brepse.css';
import '../../css/u/uxni1ac_w.css';
import '../../css/z/zurui3ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yv_brepse"/><path class="uxni1ac_w"/><path class="zurui3ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:minus-circle-twotone" {...props}></Icon>
