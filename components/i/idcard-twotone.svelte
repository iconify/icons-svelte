<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tozv2lbrl.css';
import '../../css/k/krpi41bzj.css';
import '../../css/w/w53f1mbdp.css';
import '../../css/b/bg879tbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tozv2lbrl"/><path class="krpi41bzj"/><path class="w53f1mbdp"/><path class="bg879tbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:idcard-twotone" {...props}></Icon>
