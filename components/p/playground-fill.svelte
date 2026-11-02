<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voinmcb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voinmcb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:playground-fill" {...props}></Icon>
