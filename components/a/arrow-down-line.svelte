<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df2g-2x7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="df2g-2x7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-down-line" {...props}></Icon>
