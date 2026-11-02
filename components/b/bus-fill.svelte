<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6oiutt-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6oiutt-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bus-fill" {...props}></Icon>
