<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxby_lbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxby_lbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:flag-checkered-solid" {...props}></Icon>
