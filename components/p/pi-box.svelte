<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh-c79jpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh-c79jpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pi-box" {...props}></Icon>
