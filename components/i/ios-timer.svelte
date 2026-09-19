<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opnuv-atr.css';
import '../../css/q/qirndk33c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="opnuv-atr"/><path class="qirndk33c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-timer" {...props}></Icon>
