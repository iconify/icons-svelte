<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5hlgrblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j5hlgrblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:car-window-fill" {...props}></Icon>
