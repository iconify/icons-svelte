<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiobo4jps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yiobo4jps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevron-first-solid" {...props}></Icon>
