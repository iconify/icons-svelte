<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz6h4kbwi.css';
import '../../css/c/ctvx1x6ua.css';
import '../../css/q/qrplm35by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zz6h4kbwi"/><path class="ctvx1x6ua"/><path class="qrplm35by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-beer" {...props}></Icon>
