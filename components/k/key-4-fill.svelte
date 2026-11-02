<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc52ak1ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc52ak1ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:key-4-fill" {...props}></Icon>
