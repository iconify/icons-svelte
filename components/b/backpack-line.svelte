<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q731w8b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q731w8b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:backpack-line" {...props}></Icon>
