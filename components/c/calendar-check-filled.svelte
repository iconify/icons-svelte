<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftg18_bcd.css';
import '../../css/g/gjba8cbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ftg18_bcd"/><path class="gjba8cbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-check-filled" {...props}></Icon>
