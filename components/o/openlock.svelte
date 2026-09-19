<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt_htbcmj.css';
import '../../css/a/ag187fmtm.css';
import '../../css/w/w6a8j9y3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kt_htbcmj"/><path class="ag187fmtm"/><path class="w6a8j9y3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:openlock" {...props}></Icon>
