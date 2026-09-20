<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbgk0ibde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbgk0ibde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:move-horizontal" {...props}></Icon>
