<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m62_8ratf.css';
import '../../css/y/yax8ykbmj.css';
import '../../css/d/d2ndz6b2q.css';
import '../../css/t/tfcewbbzn.css';
import '../../css/j/jwxgdac6b.css';
import '../../css/v/vxcxjnbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m62_8ratf"/><path class="yax8ykbmj"/><path class="d2ndz6b2q"/><path class="tfcewbbzn"/><path class="jwxgdac6b"/><path class="vxcxjnbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chiller-20" {...props}></Icon>
