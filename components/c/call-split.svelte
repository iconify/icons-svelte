<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh_7pnb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh_7pnb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:call-split" {...props}></Icon>
