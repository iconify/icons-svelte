<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hezo5c0_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hezo5c0_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:key-1-fill" {...props}></Icon>
