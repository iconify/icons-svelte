<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc_2pfb3v.css';
import '../../css/z/zz8dk9k1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xc_2pfb3v"/><path class="zz8dk9k1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:objective-cpp" {...props}></Icon>
