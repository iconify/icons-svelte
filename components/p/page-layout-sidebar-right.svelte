<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol0gwubmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol0gwubmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:page-layout-sidebar-right" {...props}></Icon>
