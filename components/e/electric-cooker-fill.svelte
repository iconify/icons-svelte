<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-41928fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-41928fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:electric-cooker-fill" {...props}></Icon>
