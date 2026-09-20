<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk-_uab5y.css';
import '../../css/q/qg31fgbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xk-_uab5y"/><circle class="qg31fgbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:obelisk" {...props}></Icon>
