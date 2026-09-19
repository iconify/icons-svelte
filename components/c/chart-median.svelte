<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk-i_ibgn.css';
import '../../css/y/ykc7uz8oe.css';
import '../../css/z/z17_xq-jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pk-i_ibgn"/><path class="ykc7uz8oe"/><path class="z17_xq-jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-median" {...props}></Icon>
