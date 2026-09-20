<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb_pfbb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tb_pfbb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:calendar-day-filled" {...props}></Icon>
