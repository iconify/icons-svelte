<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrn74jbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrn74jbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:archive-arrow-down-outline" {...props}></Icon>
