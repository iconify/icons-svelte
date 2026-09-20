<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8w928bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8w928bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:page-layout-sidebar-left" {...props}></Icon>
