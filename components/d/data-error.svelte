<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx4upobit.css';
import '../../css/b/b6ueueufz.css';
import '../../css/n/nvorv_bgg.css';
import '../../css/z/zs_opyb-n.css';
import '../../css/w/wquiciikb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="xx4upobit"/><circle class="b6ueueufz"/><circle class="nvorv_bgg"/><path class="zs_opyb-n"/><path class="wquiciikb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-error" {...props}></Icon>
