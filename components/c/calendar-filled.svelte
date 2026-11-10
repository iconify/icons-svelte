<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax-j1ibyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax-j1ibyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:calendar-filled" {...props}></Icon>
