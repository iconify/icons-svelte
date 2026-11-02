<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bex7p4bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bex7p4bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:carplay-line" {...props}></Icon>
