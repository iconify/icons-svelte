<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp1h03ydm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qp1h03ydm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:astuto-dark" {...props}></Icon>
