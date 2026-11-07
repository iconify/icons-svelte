<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq2hqvwyz.css';
import '../../css/q/q5070xbhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xq2hqvwyz"/><path class="q5070xbhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-to-folder-bold-duotone" {...props}></Icon>
