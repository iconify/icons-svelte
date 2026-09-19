<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8p4k7b8x.css';
import '../../css/o/o2gadtdnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8p4k7b8x"/><path class="o2gadtdnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:midjourney" {...props}></Icon>
