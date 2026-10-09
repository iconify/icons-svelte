<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxsi2dbdr.css';
import '../../css/c/cx1o0f4by.css';
import '../../css/x/xr8sjdbkj.css';
import '../../css/c/cc307ksft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cxsi2dbdr"/><path class="cx1o0f4by"/><path class="xr8sjdbkj"/><path class="cc307ksft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:contactless-48" {...props}></Icon>
