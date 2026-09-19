<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhj1p2osp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhj1p2osp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bar-chart" {...props}></Icon>
