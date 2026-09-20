<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoazkfs-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoazkfs-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chart-column-decreasing" {...props}></Icon>
