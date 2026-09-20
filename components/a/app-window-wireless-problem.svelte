<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz18_1bea.css';
import '../../css/p/p49d8zb-f.css';
import '../../css/v/v3z8t2bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz18_1bea"/><path class="p49d8zb-f"/><path class="v3z8t2bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:app-window-wireless-problem" {...props}></Icon>
