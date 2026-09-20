<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv90lrb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv90lrb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:diving-scuba-flag" {...props}></Icon>
