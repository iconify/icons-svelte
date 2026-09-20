<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0gfyd46o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0gfyd46o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:expand-horizontal" {...props}></Icon>
