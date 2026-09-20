<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp1v2sdoj.css';
import '../../css/w/wrcuzdz1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qp1v2sdoj"/><path class="wrcuzdz1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloudpi" {...props}></Icon>
