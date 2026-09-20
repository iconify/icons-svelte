<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxp3iactp.css';
import '../../css/h/hy2z1dbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="cxp3iactp"/><path class="hy2z1dbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:popup" {...props}></Icon>
