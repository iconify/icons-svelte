<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeo1qepyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zeo1qepyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dropper" {...props}></Icon>
