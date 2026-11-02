<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu-zd195g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lu-zd195g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-heart-fill" {...props}></Icon>
