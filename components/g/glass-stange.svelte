<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljf0g-bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljf0g-bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:glass-stange" {...props}></Icon>
