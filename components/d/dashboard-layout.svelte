<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yym1m5i-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yym1m5i-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:dashboard-layout" {...props}></Icon>
