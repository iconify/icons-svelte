<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s08p1sbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s08p1sbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:call-received" {...props}></Icon>
