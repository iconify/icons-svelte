<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiw619uzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiw619uzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:electric-cooker-line" {...props}></Icon>
