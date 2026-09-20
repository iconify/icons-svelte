<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo806ub4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo806ub4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:refresh-circle" {...props}></Icon>
