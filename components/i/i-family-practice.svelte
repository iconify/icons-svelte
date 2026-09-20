<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr_rtccfq.css';
import '../../css/q/q3s24obkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="xr_rtccfq"/><path class="q3s24obkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-family-practice" {...props}></Icon>
