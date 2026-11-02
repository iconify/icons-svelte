<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0evqaczm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0evqaczm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-clock-line" {...props}></Icon>
