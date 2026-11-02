<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up1nw_wyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="up1nw_wyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:button-fill" {...props}></Icon>
