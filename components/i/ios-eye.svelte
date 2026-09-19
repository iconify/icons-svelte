<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0g-o_bdg.css';
import '../../css/z/ztt_jxlej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i0g-o_bdg"/><path class="ztt_jxlej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-eye" {...props}></Icon>
